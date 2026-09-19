<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhx1jm7tb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xhx1jm7tb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:garage-4-prong" /></template>
