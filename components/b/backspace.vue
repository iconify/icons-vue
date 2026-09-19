<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2t8b4_yh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q2t8b4_yh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:backspace" /></template>
