<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_7t4lb2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_7t4lb2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:devdotto" /></template>
