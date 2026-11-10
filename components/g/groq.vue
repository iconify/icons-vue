<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qa5z70b5c.css';
import '../../css/a/aa_dfybgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="qa5z70b5c"/><path class="aa_dfybgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:groq" /></template>
