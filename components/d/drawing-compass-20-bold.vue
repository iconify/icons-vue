<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rill5m66m.css';
import '../../css/e/ei2u0fbjq.css';
import '../../css/h/hf9qlabiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rill5m66m"/><path class="ei2u0fbjq"/><path class="hf9qlabiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:drawing-compass-20-bold" /></template>
