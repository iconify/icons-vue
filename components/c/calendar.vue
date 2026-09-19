<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxb6bgbsy.css';
import '../../css/t/tyb07sbbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="gxb6bgbsy"/><path class="tyb07sbbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:calendar" /></template>
