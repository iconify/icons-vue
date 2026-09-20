<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1b6gccuq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="n1b6gccuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:drawer-left" /></template>
