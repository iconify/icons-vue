<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/atjm0035i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="atjm0035i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:crowbar" /></template>
