<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghj6zeexj.css';
import '../../css/i/i1rnhy3qh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ghj6zeexj"/><path class="i1rnhy3qh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:coin-purse-1-bold" /></template>
