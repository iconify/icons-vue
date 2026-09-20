<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6y1o92sp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="y6y1o92sp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:flags-alt-1" /></template>
