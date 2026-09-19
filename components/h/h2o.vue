<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8tf56bko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h8tf56bko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:h2o" /></template>
