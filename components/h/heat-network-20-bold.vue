<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qho2-b78i.css';
import '../../css/c/cu2uiexyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qho2-b78i"/><path class="cu2uiexyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heat-network-20-bold" /></template>
