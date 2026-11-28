<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_c5r46wn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_c5r46wn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:input-solid" /></template>
