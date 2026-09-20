<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/is7he1yqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="is7he1yqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:draggable-horizontal" /></template>
