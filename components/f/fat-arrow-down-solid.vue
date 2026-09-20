<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/een_dgbbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="een_dgbbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:fat-arrow-down-solid" /></template>
