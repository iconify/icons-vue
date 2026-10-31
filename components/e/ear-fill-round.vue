<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tx_-4bcbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tx_-4bcbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ear-fill-round" /></template>
