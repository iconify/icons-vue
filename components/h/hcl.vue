<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7tdrk9ta.css';
import '../../css/g/g3yfe1b-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u7tdrk9ta"/><path class="g3yfe1b-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:hcl" /></template>
