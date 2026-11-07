<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wygv-re1g.css';
import '../../css/t/t6-wmjb2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wygv-re1g"/><path class="t6-wmjb2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:crop-bold" /></template>
