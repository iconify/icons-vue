<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftgbccc-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ftgbccc-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:function-duotone-round" /></template>
