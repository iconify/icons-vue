<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxz5aqj2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxz5aqj2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:heartbeat-24px" /></template>
