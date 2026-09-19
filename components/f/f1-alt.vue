<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ryn_ssbhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ryn_ssbhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:f1-alt" /></template>
