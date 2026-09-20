<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utsv-3-af.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="utsv-3-af"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:coffee-takeaway-cup-remix" /></template>
