<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_0_hhb-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x_0_hhb-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:align-horizontal-justify-start" /></template>
