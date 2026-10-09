<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzjiqabtu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xzjiqabtu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:filter-20" /></template>
