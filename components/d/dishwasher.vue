<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jw5nfdb1w.css';
import '../../css/n/nj83mcbyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jw5nfdb1w"/><path class="nj83mcbyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dishwasher" /></template>
