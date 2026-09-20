<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbn3k0brm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tbn3k0brm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bar-chart-2-horizontal-start-sharp-fill" /></template>
