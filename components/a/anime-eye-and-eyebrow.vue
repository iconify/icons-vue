<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6fhxyvqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="v6fhxyvqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:anime-eye-and-eyebrow" /></template>
