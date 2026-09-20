<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfahfob6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tfahfob6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:copy-one-outline" /></template>
