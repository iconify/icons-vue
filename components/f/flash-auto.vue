<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6jsscczo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":416,"height":456};
const content = `<path class="k6jsscczo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:flash-auto" /></template>
