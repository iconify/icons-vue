<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h3s-_cc2g.css';
import '../../css/m/m8bqvccua.css';
import '../../css/f/ffwvq5baq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="h3s-_cc2g"/><path class="m8bqvccua"/><ellipse transform="rotate(30 23.477 12.594)" class="ffwvq5baq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:green-heart" /></template>
