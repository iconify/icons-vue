<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usd_jbcxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="usd_jbcxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:handbag-round" /></template>
