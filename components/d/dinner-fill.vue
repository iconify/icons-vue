<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4rj83b0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4rj83b0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dinner-fill" /></template>
