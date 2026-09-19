<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8nzoibcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n8nzoibcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:codacy" /></template>
