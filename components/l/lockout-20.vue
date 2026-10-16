<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rx6vej9mh.css';
import '../../css/q/qjh6c2bbs.css';
import '../../css/x/xhkmldn9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rx6vej9mh"/><path class="qjh6c2bbs"/><path class="xhkmldn9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lockout-20" /></template>
