<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h86di18bu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h86di18bu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:brodie-helmet" /></template>
