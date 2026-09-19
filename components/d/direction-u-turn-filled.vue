<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/saty3nwhh.css';
import '../../css/n/nhm009g7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="saty3nwhh"/><path class="nhm009g7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:direction-u-turn-filled" /></template>
