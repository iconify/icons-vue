<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzqbacb6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tzqbacb6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:letter-xx" /></template>
