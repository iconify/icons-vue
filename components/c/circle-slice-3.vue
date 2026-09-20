<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_uv4jtqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_uv4jtqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:circle-slice-3" /></template>
