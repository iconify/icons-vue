<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njje8mjim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="njje8mjim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:corner-up-left-line" /></template>
