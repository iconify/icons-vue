<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_s_vqb5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="q_s_vqb5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:display-dot-matrix" /></template>
