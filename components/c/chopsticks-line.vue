<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv3n77kdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nv3n77kdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chopsticks-line" /></template>
