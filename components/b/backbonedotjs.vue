<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kx6xl1bur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kx6xl1bur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:backbonedotjs" /></template>
