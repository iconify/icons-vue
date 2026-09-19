<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5l_z9buq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="b5l_z9buq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:inkscape" /></template>
