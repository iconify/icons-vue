<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rai4yqb2e.css';
import '../../css/b/bwuhri6fh.css';
import '../../css/m/msv3b6bmh.css';
import '../../css/k/khc4xk74b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rai4yqb2e"/><path class="bwuhri6fh"/><path class="msv3b6bmh"/><path class="khc4xk74b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ghost-smile-bold-duotone" /></template>
