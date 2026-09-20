<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zs2rhf85g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zs2rhf85g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:dice" /></template>
