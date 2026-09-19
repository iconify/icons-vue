<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/gpiv9dj0x.css';
import '../../css/m/mldtnhb8i.css';
import '../../css/v/v84njyepy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="gpiv9dj0x"/><path class="mldtnhb8i"/><path class="v84njyepy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:magnifying-glass-tilted-right" /></template>
