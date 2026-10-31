<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qipb8obgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qipb8obgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:credit-card-plus-corner-fill-round" /></template>
