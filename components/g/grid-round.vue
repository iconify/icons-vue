<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uuc2r_fef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uuc2r_fef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:grid-round" /></template>
