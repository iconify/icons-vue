<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/df474cc-n.css';
import '../../css/y/yxgyrcb-d.css';
import '../../css/x/xqhhzqtle.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="df474cc-n"/><path class="yxgyrcb-d"/><path class="xqhhzqtle"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heat-meter-48-bold" /></template>
