<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/od64xkb-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="od64xkb-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:copy" /></template>
