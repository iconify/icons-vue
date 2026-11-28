<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w08qh4blk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w08qh4blk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:fold-vertical-solid" /></template>
