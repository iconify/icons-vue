<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxkm_rblg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hxkm_rblg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:calendar-check" /></template>
