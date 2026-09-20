<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avt9bib9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="avt9bib9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:exclaimation-solid" /></template>
