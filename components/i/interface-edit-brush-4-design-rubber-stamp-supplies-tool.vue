<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/widsseezf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="widsseezf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-edit-brush-4-design-rubber-stamp-supplies-tool" /></template>
