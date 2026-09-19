<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8o2mmbrq.css';
import '../../css/t/t_9pnl1bo.css';
import '../../css/z/zvvso5rkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n8o2mmbrq"/><rect class="t_9pnl1bo"/><rect class="zvvso5rkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:align-horizontal-space-between-filled" /></template>
