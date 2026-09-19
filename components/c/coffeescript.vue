<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwhmc8byn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="vwhmc8byn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:coffeescript" /></template>
