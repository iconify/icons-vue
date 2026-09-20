<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5rsdac0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q5rsdac0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:logseq" /></template>
