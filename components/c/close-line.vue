<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ex1x372fr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ex1x372fr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:close-line" /></template>
