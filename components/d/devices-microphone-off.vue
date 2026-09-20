<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvk4_jk4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vvk4_jk4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:devices-microphone-off" /></template>
