<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9f5b6tbj.css';
import '../../css/r/r6aez23ym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v9f5b6tbj"/><path class="r6aez23ym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-alarm-exclamation" /></template>
