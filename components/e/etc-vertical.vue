<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zz_y34baq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zz_y34baq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:etc-vertical" /></template>
