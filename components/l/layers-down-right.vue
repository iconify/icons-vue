<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzw2gxtkm.css';
import '../../css/f/f6sqxlbwl.css';
import '../../css/j/j2p94mlao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uzw2gxtkm"/><path class="f6sqxlbwl"/><path class="j2p94mlao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:layers-down-right" /></template>
