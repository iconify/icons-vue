<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1t0mblgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d1t0mblgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:brightness-low-solid" /></template>
