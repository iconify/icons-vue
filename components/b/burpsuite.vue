<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fduf--fxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="fduf--fxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:burpsuite" /></template>
