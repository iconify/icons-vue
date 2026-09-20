<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfn4_0bxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zfn4_0bxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:circle" /></template>
