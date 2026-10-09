<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qkz17l6zd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qkz17l6zd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:crown-20-bold" /></template>
