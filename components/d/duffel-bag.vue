<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1od96b5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h1od96b5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:duffel-bag" /></template>
