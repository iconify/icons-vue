<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1r22d5_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t1r22d5_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:heartbeat-2-line" /></template>
