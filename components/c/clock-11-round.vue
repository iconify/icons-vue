<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xt84qfb8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xt84qfb8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clock-11-round" /></template>
