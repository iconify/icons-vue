<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m243ofbec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="m243ofbec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:groq" /></template>
