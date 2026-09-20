<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6hq5bt1d.css';
import '../../css/m/m-9tadk8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i6hq5bt1d"/><path class="m-9tadk8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:electronics-fuse-bold" /></template>
