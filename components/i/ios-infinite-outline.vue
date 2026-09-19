<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qcab2sbna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qcab2sbna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-infinite-outline" /></template>
