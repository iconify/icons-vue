<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trcnswy-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="trcnswy-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:charging-pile-2-line" /></template>
