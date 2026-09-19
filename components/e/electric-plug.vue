<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/b1n5agh6p.css';
import '../../css/y/y41i_nf7f.css';
import '../../css/c/cgto4lbtn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="b1n5agh6p"/><path class="y41i_nf7f"/><path class="cgto4lbtn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:electric-plug" /></template>
