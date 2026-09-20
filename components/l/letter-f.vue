<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lh7gp0bsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lh7gp0bsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:letter-f" /></template>
