<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ao__mmbtc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ao__mmbtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:flow-loop-limit" /></template>
