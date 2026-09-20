<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thas5ub-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="thas5ub-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:erlenmeyer-flask-remix" /></template>
