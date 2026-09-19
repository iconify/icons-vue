<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pq108nbam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pq108nbam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:headset" /></template>
