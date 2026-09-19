<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/ztj5prbss.css';
import '../../css/z/z7oqzzbjb.css';
import '../../css/i/i8zwbnb2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="ztj5prbss"/><path class="z7oqzzbjb"/><path class="i8zwbnb2d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:hand-with-index-finger-and-thumb-crossed-light" /></template>
