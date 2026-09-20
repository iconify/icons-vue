<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lw448hmuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lw448hmuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-t-octagon" /></template>
