<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8hps5hrz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="h8hps5hrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hand-horns-duo" /></template>
