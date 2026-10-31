<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmibc4bxr.css';
import '../../css/x/xr8ziu2ag.css';
import '../../css/a/a31qyebym.css';
import '../../css/m/mm9e_xqhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="nmibc4bxr"/><path class="xr8ziu2ag"/><path class="a31qyebym"/><path class="mm9e_xqhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:cyprus" /></template>
