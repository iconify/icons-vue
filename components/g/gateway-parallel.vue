<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eja77yp7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="eja77yp7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:gateway-parallel" /></template>
