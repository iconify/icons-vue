<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xeah8-6tb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xeah8-6tb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:log-out-circle" /></template>
