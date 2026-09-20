<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyieymyrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qyieymyrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alpha-q-box" /></template>
