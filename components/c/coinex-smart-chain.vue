<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/olirf2bph.css';
import '../../css/q/qz4yqq5kt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="olirf2bph"/><path class="qz4yqq5kt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:coinex-smart-chain" /></template>
