<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o70vwv53g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o70vwv53g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-arrow-round-back" /></template>
