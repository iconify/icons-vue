<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpdd8_pnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fpdd8_pnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dots-horizontal-rounded-filled" /></template>
