<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfmbfrbpt.css';
import '../../css/g/ga2dqzb8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qfmbfrbpt"/><path class="ga2dqzb8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bread" /></template>
