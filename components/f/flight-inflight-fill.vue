<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkyvgqa0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mkyvgqa0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flight-inflight-fill" /></template>
