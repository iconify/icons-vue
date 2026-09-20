<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yr9hupbuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="yr9hupbuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:jewellery-14" /></template>
