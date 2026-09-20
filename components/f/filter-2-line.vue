<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6ri12e_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i6ri12e_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:filter-2-line" /></template>
