<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqfc6_h8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dqfc6_h8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-brightness-half" /></template>
