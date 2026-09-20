<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fr4pidc2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fr4pidc2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:flat-head-thumb-tack" /></template>
