<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rp2l--bwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rp2l--bwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:distribute-horizontal-left" /></template>
