<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfz9u0b1c.css';
import '../../css/a/ao__mmbtc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qfz9u0b1c secondary"/><path class="ao__mmbtc primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:flow-loop-limit-duo" /></template>
