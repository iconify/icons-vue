<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sozdzcb0a.css';
import '../../css/r/ris-r3boe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sozdzcb0a"/><path clip-rule="evenodd" class="ris-r3boe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:chart-bar-stacked-filled" /></template>
