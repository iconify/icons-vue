<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ub0s4ex6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ub0s4ex6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrow-right-fill" /></template>
