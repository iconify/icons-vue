<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tz12mvlvv.css';
import '../../css/x/xnrsw1b2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tz12mvlvv"/><path class="xnrsw1b2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:fish-alt" /></template>
