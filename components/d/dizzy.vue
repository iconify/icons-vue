<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mi2u0qhkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mi2u0qhkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:dizzy" /></template>
