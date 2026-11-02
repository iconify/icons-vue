<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtm_h7umf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xtm_h7umf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:game-1-line" /></template>
