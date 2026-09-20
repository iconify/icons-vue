<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qamy95zgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qamy95zgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:dog-side" /></template>
