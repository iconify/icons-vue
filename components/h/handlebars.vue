<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgifm_d5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="jgifm_d5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:handlebars" /></template>
