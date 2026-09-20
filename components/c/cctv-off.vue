<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trk91ybqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="trk91ybqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cctv-off" /></template>
