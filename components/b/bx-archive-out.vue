<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwj-tdbmb.css';
import '../../css/x/xcy8lybpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nwj-tdbmb"/><path class="xcy8lybpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-archive-out" /></template>
