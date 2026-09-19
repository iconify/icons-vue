<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mn13ih9-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="mn13ih9-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:cart-flatbed" /></template>
