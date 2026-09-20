<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-ccf1npc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-ccf1npc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-decrease-fill" /></template>
