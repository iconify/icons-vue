<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4k0k2bhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="k4k0k2bhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:aspect-ratio" /></template>
