<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km_1fum4q.css';
import '../../css/u/urac6lrqz.css';
import '../../css/y/yfeqx5ccz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="km_1fum4q"/><path class="urac6lrqz"/><path class="yfeqx5ccz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:futures-48" /></template>
