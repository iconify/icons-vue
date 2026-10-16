<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqiq30b6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="aqiq30b6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hot-rock-20-bold" /></template>
