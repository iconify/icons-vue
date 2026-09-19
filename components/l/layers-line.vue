<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvsxqn9yz.css';
import '../../css/r/r6h-a0bkr.css';
import '../../css/s/s-bn8xbic.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 yvsxqn9yz"/><path class="clr-i-outline clr-i-outline-path-2 r6h-a0bkr"/><path class="clr-i-outline clr-i-outline-path-3 s-bn8xbic"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:layers-line" /></template>
