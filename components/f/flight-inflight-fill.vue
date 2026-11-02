<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qax5_jh4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qax5_jh4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flight-inflight-fill" /></template>
