<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0monobga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t0monobga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:globe-line" /></template>
