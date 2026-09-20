<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1c-26sug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":65,"height":65,"left":33};
const content = `<path class="z1c-26sug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:chunk" /></template>
