<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glw37vbyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="glw37vbyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:codeac" /></template>
