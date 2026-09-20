<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h98b_5bwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h98b_5bwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:credit-card-clock" /></template>
