<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6e4s3bwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s6e4s3bwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:chanterelles" /></template>
