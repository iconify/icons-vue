<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/p7s1n_b6l.css';
import '../../css/s/sxoa9bbug.css';
import '../../css/l/lpbf7fb9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="p7s1n_b6l"/><path class="sxoa9bbug"/><path class="lpbf7fb9k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:leafy-green" /></template>
