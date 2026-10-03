<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1c24zb_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1c24zb_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:dartboard" /></template>
