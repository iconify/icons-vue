<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yg7wgbbdt.css';
import '../../css/e/efsxz5dnj.css';
import '../../css/r/rckjn3l5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yg7wgbbdt"/><path class="efsxz5dnj"/><path class="rckjn3l5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-copy" /></template>
