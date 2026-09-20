<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kg3ameb8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kg3ameb8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:arrow-big-down" /></template>
