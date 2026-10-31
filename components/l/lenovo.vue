<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jk4_q26ia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jk4_q26ia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:lenovo" /></template>
