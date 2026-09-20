<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cv6nmjb6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cv6nmjb6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:document" /></template>
