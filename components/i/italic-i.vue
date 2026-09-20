<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4mdfm72f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f4mdfm72f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:italic-i" /></template>
