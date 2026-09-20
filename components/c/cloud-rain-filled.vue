<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjy-gzb2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="gjy-gzb2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:cloud-rain-filled" /></template>
