<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nf_ef62wo.css';
import '../../css/i/iqccs38dr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nf_ef62wo"/><path class="iqccs38dr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:calendar-week" /></template>
