<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/veeb6g1ym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="veeb6g1ym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:beer-fill" /></template>
