<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xko57xb5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xko57xb5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:drinking-water" /></template>
