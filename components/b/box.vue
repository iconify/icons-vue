<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjy8i0bur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fjy8i0bur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:box" /></template>
