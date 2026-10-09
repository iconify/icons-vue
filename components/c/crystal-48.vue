<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7qd3ubqx.css';
import '../../css/j/j4kecacgy.css';
import '../../css/z/ztnyhokgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m7qd3ubqx"/><path class="j4kecacgy"/><path class="ztnyhokgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:crystal-48" /></template>
