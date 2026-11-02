<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtjmx2rke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xtjmx2rke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:lipstick-fill" /></template>
