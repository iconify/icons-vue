<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fu6qz_i4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fu6qz_i4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:docspell-dark" /></template>
