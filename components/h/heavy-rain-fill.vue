<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzine-gxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tzine-gxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:heavy-rain-fill" /></template>
