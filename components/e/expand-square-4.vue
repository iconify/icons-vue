<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3d8sv4oq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="k3d8sv4oq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:expand-square-4" /></template>
