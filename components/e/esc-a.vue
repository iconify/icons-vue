<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-29u-bwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s-29u-bwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:esc-a" /></template>
