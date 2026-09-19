<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1o22uoyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="u1o22uoyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:flying-saucer" /></template>
