<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5hsqdgum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="p5hsqdgum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:crystal" /></template>
