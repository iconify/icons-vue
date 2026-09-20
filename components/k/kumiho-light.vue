<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ji862o97d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ji862o97d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kumiho-light" /></template>
