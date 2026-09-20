<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4kyljbeg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q4kyljbeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:chess-queen-filled" /></template>
