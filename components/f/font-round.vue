<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbbon8b5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hbbon8b5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:font-round" /></template>
