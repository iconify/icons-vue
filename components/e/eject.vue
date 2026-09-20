<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yyz43k57l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yyz43k57l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:eject" /></template>
