<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knur75qgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="knur75qgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:lock-locked" /></template>
