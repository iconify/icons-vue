<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oa6l2nb1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oa6l2nb1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cloud-rain-wind-filled" /></template>
