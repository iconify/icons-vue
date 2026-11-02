<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m236ioque.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m236ioque"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:escalator-up-line" /></template>
