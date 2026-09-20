<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsmsv2kzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dsmsv2kzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:heartbeat-2-fill" /></template>
