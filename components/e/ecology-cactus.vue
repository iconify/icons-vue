<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdtmjzblg.css';
import '../../css/g/gx3ml1b9y.css';
import '../../css/l/lzz9wzsya.css';
import '../../css/i/isjb93bxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pdtmjzblg"/><path class="gx3ml1b9y"/><path class="lzz9wzsya"/><path class="isjb93bxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:ecology-cactus" /></template>
