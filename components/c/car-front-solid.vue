<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lc2tlw_6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lc2tlw_6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:car-front-solid" /></template>
