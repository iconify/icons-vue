<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbpl-x4go.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zbpl-x4go"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-pulse-strong" /></template>
