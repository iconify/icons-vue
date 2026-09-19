<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0mr6uruh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="r0mr6uruh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:homebrew" /></template>
