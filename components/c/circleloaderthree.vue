<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6yhc8bib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":960,"height":960};
const content = `<path class="g6yhc8bib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:circleloaderthree" /></template>
