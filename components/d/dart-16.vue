<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7z2-nmdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w7z2-nmdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nonicons:dart-16" /></template>
