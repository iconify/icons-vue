<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjozsnoyg.css';
import '../../css/q/qwzgryv0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjozsnoyg"/><path class="qwzgryv0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cloud-snow-line" /></template>
