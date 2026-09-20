<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cltl31bns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cltl31bns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:chart-pie-3-filled" /></template>
