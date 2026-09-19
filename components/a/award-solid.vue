<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsi1s7btx.css';
import '../../css/n/nhkex-b_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dsi1s7btx"/><path clip-rule="evenodd" class="nhkex-b_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:award-solid" /></template>
