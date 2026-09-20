<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fsun6_jdx.css';
import '../../css/i/igyvn5baq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fsun6_jdx"/><path class="igyvn5baq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:bcd" /></template>
