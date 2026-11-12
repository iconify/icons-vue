<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxp5dgbxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wxp5dgbxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cal-com-dark" /></template>
