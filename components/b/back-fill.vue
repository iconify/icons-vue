<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4_pnfccj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y4_pnfccj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:back-fill" /></template>
