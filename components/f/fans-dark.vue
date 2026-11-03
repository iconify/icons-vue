<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2delqbxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="d2delqbxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:fans-dark" /></template>
