<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwck-jbvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="iwck-jbvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:gitkraken" /></template>
