<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyv4_tbpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="dyv4_tbpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:hugo" /></template>
