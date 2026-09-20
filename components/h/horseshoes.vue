<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpc-6mina.css';
import '../../css/x/xczq1jt6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lpc-6mina"/><path class="xczq1jt6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:horseshoes" /></template>
