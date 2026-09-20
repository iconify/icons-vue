<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ila-1wb8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ila-1wb8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:abs-line" /></template>
