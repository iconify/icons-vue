<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsx3oj1sf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nsx3oj1sf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:firebase-solid" /></template>
