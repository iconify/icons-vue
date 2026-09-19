<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u49fm9evw.css';
import '../../css/f/fzn8913pw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="u49fm9evw"/><path class="fzn8913pw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:ansys" /></template>
