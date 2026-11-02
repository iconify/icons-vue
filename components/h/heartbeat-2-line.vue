<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwooc4-dq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zwooc4-dq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:heartbeat-2-line" /></template>
