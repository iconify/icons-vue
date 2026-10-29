<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2x5yebma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="m2x5yebma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:firebase" /></template>
