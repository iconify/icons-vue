<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sif1ckb6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sif1ckb6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:exchange-dollar-fill" /></template>
