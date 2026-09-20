<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcb_rnbtp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pcb_rnbtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:color-blind-bold" /></template>
