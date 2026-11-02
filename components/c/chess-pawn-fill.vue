<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnm_4wbwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tnm_4wbwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chess-pawn-fill" /></template>
