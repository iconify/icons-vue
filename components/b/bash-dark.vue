<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jd4435b7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jd4435b7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:bash-dark" /></template>
