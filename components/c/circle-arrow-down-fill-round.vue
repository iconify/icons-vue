<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvoi15yhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yvoi15yhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-arrow-down-fill-round" /></template>
