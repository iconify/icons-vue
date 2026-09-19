<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1sjshbrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="u1sjshbrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:drupal" /></template>
