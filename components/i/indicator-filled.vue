<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4h07njtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q4h07njtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:indicator-filled" /></template>
