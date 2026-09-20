<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4l_q6qfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t4l_q6qfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-desktop-cancel" /></template>
