<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2n7uvblv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="f2n7uvblv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:hat-man-filled" /></template>
