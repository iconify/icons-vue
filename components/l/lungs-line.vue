<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/goc14zbnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="goc14zbnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:lungs-line" /></template>
