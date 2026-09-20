<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isb_qbbaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="isb_qbbaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:arrow-down-narrow-wide" /></template>
