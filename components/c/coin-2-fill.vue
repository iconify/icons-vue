<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k72n2-yze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k72n2-yze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:coin-2-fill" /></template>
