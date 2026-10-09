<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qt1m1hp9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qt1m1hp9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:align-left-20-bold" /></template>
