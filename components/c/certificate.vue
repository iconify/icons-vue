<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdcvev7wr.css';
import '../../css/f/fbeas_klm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdcvev7wr duoicon-primary-layer"/><path class="duoicon-secondary-layer fbeas_klm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:certificate" /></template>
