<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u30j6c78d.css';
import '../../css/p/p_6tgjbsm.css';
import '../../css/y/yiybycb-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="u30j6c78d"/><path class="p_6tgjbsm"/><path class="yiybycb-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:host-outline-alerted" /></template>
