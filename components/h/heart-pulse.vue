<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2owkl-9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n2owkl-9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:heart-pulse" /></template>
