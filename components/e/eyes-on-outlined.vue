<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dg9j3pb4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dg9j3pb4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:eyes-on-outlined" /></template>
