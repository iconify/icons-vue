<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mey0rqboh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mey0rqboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:department-line" /></template>
