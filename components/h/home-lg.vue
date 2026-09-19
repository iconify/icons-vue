<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugq91db8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ugq91db8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:home-lg" /></template>
