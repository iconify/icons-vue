<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv0sx3-bi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sv0sx3-bi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:align-horizontal-justify-start" /></template>
