<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6fl9mbqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6fl9mbqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-dashed-two-tone" /></template>
