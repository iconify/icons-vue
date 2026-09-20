<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7hgixbly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m7hgixbly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:apple" /></template>
