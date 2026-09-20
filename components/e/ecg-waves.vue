<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nudrhyb5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="nudrhyb5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:ecg-waves" /></template>
