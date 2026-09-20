<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prh1_ibol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="prh1_ibol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:hierarchy-14-remix" /></template>
