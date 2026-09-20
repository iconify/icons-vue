<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j62at_pho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j62at_pho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:lightbulb-auto" /></template>
