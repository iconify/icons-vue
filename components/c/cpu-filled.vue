<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eccbwzb_m.css';
import '../../css/n/nq39egbbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eccbwzb_m"/><path class="nq39egbbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:cpu-filled" /></template>
