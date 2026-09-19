<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m599ys8mi.css';
import '../../css/m/mgsi99bfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m599ys8mi"/><path class="mgsi99bfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:car-battery" /></template>
