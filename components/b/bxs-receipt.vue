<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ml_qa0sac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ml_qa0sac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-receipt" /></template>
