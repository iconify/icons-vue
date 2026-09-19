<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4lnkvbol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="g4lnkvbol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:gradle" /></template>
