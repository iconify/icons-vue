<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmxsu8bjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmxsu8bjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:forward-step" /></template>
