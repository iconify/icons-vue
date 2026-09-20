<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wzk3pub-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wzk3pub-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:bookmark-o" /></template>
