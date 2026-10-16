<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbk_it7zx.css';
import '../../css/m/m9fufbb8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mbk_it7zx"/><path class="m9fufbb8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:delivery-robot-20-bold" /></template>
