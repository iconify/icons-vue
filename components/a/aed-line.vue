<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1_q279fv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e1_q279fv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:aed-line" /></template>
