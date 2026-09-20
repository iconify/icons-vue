<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghonb3bha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ghonb3bha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:doordash-dark" /></template>
