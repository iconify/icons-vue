<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-7nacbwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="p-7nacbwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:git" /></template>
