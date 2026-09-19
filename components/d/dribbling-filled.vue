<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pd_g2tb1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pd_g2tb1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dribbling-filled" /></template>
