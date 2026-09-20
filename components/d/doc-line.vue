<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trp5kebab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="trp5kebab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:doc-line" /></template>
