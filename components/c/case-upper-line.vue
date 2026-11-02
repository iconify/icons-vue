<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awc4shbfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="awc4shbfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:case-upper-line" /></template>
