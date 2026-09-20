<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3srz291p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m3srz291p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:brand-dribbble-solid" /></template>
