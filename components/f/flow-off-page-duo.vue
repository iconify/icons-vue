<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt1z6xbjk.css';
import '../../css/p/plng_wb5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary wt1z6xbjk"/><path class="plng_wb5t primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:flow-off-page-duo" /></template>
