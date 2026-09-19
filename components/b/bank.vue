<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrr_t1bwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qrr_t1bwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:bank" /></template>
