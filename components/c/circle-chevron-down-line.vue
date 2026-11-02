<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdi8facum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rdi8facum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:circle-chevron-down-line" /></template>
