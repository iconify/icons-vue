<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3ft7sbvr.css';
import '../../css/p/p-jt3neah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h3ft7sbvr"/><path class="p-jt3neah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:haus" /></template>
