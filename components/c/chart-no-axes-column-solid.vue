<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvpi71b7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wvpi71b7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chart-no-axes-column-solid" /></template>
