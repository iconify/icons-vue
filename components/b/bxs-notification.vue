<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h68a5vtzz.css';
import '../../css/h/hp_yerj1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="h68a5vtzz"/><path class="hp_yerj1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-notification" /></template>
