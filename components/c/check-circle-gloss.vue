<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/me2gmwbmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="me2gmwbmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:check-circle-gloss" /></template>
