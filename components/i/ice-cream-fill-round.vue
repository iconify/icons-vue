<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_w7_5kaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_w7_5kaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ice-cream-fill-round" /></template>
