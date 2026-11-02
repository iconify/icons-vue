<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/std5kpb1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="std5kpb1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrow-right-down-circle-fill" /></template>
