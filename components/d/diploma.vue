<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2bylrb9j.css';
import '../../css/i/ijc0stb4c.css';
import '../../css/x/x3n8gwoar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s2bylrb9j"/><path class="ijc0stb4c"/><path class="x3n8gwoar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:diploma" /></template>
