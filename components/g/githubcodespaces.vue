<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjry_ebno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="tjry_ebno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:githubcodespaces" /></template>
