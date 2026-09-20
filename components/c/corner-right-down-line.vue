<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfgcmz94w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pfgcmz94w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:corner-right-down-line" /></template>
