<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgk3i7bfw.css';
import '../../css/g/g5jh10vug.css';
import '../../css/k/ko92zebxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sgk3i7bfw"/><path class="g5jh10vug"/><path class="ko92zebxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:ear-outline" /></template>
