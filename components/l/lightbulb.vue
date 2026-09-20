<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1kfb4bal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t1kfb4bal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:lightbulb" /></template>
