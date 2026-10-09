<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4v-c_q2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x4v-c_q2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:layout-grid-20" /></template>
