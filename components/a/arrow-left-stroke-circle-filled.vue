<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kk66pobvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kk66pobvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-left-stroke-circle-filled" /></template>
