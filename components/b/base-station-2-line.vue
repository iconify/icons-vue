<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xz2gqrxrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xz2gqrxrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:base-station-2-line" /></template>
