<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pw4_v6bmk.css';
import '../../css/n/ntfhc6rnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pw4_v6bmk"/><path class="ntfhc6rnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:function-argument-rtl" /></template>
