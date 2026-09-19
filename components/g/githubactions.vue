<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8g3supcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="l8g3supcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:githubactions" /></template>
