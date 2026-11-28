<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_1ac_b9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_1ac_b9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:layers-dashed-solid" /></template>
