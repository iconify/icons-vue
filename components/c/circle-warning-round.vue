<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2orr_bkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2orr_bkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-warning-round" /></template>
