<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4yhcfbyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z4yhcfbyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:align-vertical-space-between" /></template>
