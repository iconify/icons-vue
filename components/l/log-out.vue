<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hltfq1i2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hltfq1i2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:log-out" /></template>
