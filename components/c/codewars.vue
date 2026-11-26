<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofk5kdpol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ofk5kdpol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:codewars" /></template>
