<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/ql44vfbab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ql44vfbab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ai-mic" /></template>
