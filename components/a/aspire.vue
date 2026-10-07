<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rodc2fbdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="rodc2fbdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:aspire" /></template>
