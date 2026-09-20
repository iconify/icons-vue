<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5qi60--x.css';
import '../../css/z/zqip_ybwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r5qi60--x"/><path class="zqip_ybwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:chat" /></template>
