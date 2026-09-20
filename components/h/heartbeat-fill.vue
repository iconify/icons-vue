<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofc-ngbjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ofc-ngbjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:heartbeat-fill" /></template>
