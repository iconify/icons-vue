<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8781o6pz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8781o6pz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:align-arrow-right-line" /></template>
