<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4-38zb6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g4-38zb6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:badminton-line" /></template>
