<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkom64bwh.css';
import '../../css/v/vk7tt5b4s.css';
import '../../css/u/u_l71ebni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lkom64bwh"/><path class="vk7tt5b4s"/><path class="u_l71ebni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ksuite-mail-dark" /></template>
