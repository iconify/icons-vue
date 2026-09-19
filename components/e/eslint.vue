<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwyv0accm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="xwyv0accm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:eslint" /></template>
