<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ut7pyrqfx.css';
import '../../css/z/zsi22_bxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ut7pyrqfx"/><path class="zsi22_bxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:blinko" /></template>
