<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jio9igvay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jio9igvay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:antenna-bars-4" /></template>
