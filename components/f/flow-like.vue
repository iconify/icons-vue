<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rku15hbsi.css';
import '../../css/p/pp9v2l8_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rku15hbsi"/><path class="pp9v2l8_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:flow-like" /></template>
