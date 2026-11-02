<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xf_ijmbfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xf_ijmbfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bluetooth-fill" /></template>
