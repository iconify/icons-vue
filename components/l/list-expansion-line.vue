<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-bofsbdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-bofsbdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:list-expansion-line" /></template>
