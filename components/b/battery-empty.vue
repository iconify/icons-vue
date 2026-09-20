<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ju2p32bfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="ju2p32bfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:battery-empty" /></template>
