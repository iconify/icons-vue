<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtf55bc4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xtf55bc4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-battery-low" /></template>
