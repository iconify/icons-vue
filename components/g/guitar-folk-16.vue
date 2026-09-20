<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljsqm-boc.css';
import '../../css/d/dklea-b1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ljsqm-boc"/><path class="dklea-b1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:guitar-folk-16" /></template>
