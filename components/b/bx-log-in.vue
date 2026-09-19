<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrg0c1b_k.css';
import '../../css/d/d01u25bof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qrg0c1b_k"/><path class="d01u25bof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-log-in" /></template>
