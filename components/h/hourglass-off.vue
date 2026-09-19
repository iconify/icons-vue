<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ksz-h4b4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ksz-h4b4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:hourglass-off" /></template>
