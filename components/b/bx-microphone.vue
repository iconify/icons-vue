<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t20u6eccm.css';
import '../../css/y/yrtryqu9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t20u6eccm"/><path class="yrtryqu9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-microphone" /></template>
