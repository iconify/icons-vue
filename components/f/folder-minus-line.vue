<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqk1bib6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eqk1bib6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-minus-line" /></template>
