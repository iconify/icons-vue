<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ts946kbax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ts946kbax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:grok-fill" /></template>
