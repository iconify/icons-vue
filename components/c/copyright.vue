<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyu5r4bdv.css';
import '../../css/p/pyral_92n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cyu5r4bdv"/><path class="pyral_92n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:copyright" /></template>
