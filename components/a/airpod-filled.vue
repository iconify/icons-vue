<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pumdp1b0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pumdp1b0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:airpod-filled" /></template>
