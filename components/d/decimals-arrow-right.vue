<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xixnvzb-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xixnvzb-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:decimals-arrow-right" /></template>
