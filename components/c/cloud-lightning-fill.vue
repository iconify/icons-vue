<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ot_90ghjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ot_90ghjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cloud-lightning-fill" /></template>
