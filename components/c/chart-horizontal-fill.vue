<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnzcnch8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pnzcnch8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-horizontal-fill" /></template>
