<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1yx6v2_d.css';
import '../../css/t/tds6hxauo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z1yx6v2_d"/><path class="tds6hxauo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:apple-48" /></template>
