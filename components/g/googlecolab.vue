<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4q4o7bdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="c4q4o7bdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:googlecolab" /></template>
