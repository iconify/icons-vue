<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nm6y613bm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="nm6y613bm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:graph-filled" /></template>
