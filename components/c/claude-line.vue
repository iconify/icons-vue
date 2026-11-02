<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vd4m3ixzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vd4m3ixzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:claude-line" /></template>
