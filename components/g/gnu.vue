<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etv1psb6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="etv1psb6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:gnu" /></template>
