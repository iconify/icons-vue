<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oi2mxu8vr.css';
import '../../css/e/e1wjloqot.css';
import '../../css/z/zd51tnb1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oi2mxu8vr"/><path class="e1wjloqot"/><path class="zd51tnb1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:filter-x-48-bold" /></template>
