<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eoqv9k94x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eoqv9k94x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:camel" /></template>
