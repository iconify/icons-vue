<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n39e69h7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="n39e69h7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:linear" /></template>
