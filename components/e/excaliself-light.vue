<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzr8gqboc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fzr8gqboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:excaliself-light" /></template>
