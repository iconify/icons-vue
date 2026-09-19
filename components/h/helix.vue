<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6zjh8b-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="c6zjh8b-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:helix" /></template>
