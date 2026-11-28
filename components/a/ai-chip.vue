<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsaxc_miu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dsaxc_miu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:ai-chip" /></template>
