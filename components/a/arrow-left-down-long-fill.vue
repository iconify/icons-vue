<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tuabpnbfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tuabpnbfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-left-down-long-fill" /></template>
