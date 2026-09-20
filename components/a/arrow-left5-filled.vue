<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4o6kcc9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q4o6kcc9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-left5-filled" /></template>
