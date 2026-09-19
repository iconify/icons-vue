<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/in-8debth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="in-8debth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:d-and-d-beyond" /></template>
