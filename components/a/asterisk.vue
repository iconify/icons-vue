<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fr6h1qbfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fr6h1qbfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:asterisk" /></template>
