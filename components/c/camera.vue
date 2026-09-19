<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/em5dqch8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="em5dqch8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:camera" /></template>
