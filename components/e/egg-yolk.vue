<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/caw1diebi.css';
import '../../css/s/sxij2rbwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="caw1diebi"/><path class="sxij2rbwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:egg-yolk" /></template>
