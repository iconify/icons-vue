<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/woom3jbhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="woom3jbhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:drizzle" /></template>
