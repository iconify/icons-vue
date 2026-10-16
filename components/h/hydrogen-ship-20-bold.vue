<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwcpavbfl.css';
import '../../css/v/vcbhgbcuw.css';
import '../../css/r/r9oealbdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="iwcpavbfl"/><path class="vcbhgbcuw"/><path class="r9oealbdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydrogen-ship-20-bold" /></template>
