<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ml3okhbxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ml3okhbxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:discordjs" /></template>
