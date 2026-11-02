<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uo6cfv3dq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uo6cfv3dq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hammer-line" /></template>
