<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prrl5rjsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="prrl5rjsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:hotel-laundry-remix" /></template>
