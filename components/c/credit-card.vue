<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pa5fotm2d.css';
import '../../css/w/w__f9-ryl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pa5fotm2d"/><path class="w__f9-ryl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:credit-card" /></template>
