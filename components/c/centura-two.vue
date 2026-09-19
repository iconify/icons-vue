<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpf5xon0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpf5xon0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:centura-two" /></template>
