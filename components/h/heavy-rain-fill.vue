<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofaq-pqxl.css';
import '../../css/p/ph8y6rbyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ofaq-pqxl"/><path class="ph8y6rbyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:heavy-rain-fill" /></template>
