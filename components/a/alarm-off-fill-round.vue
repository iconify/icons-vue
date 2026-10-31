<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfpyk5bkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qfpyk5bkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:alarm-off-fill-round" /></template>
