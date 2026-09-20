<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnzim0yoo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cnzim0yoo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:jellyfish-outline" /></template>
