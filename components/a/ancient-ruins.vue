<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4nf9vrpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h4nf9vrpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ancient-ruins" /></template>
