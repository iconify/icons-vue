<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6dd8jb9u.css';
import '../../css/w/w4coxzjvw.css';
import '../../css/u/u3n9vcbth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l6dd8jb9u"/><path class="w4coxzjvw"/><path class="u3n9vcbth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cassette-20-bold" /></template>
