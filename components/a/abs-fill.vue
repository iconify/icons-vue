<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hp27x7h3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hp27x7h3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:abs-fill" /></template>
