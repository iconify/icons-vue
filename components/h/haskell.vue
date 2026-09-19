<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9q1n_b5d.css';
import '../../css/a/abljxkb8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="p9q1n_b5d"/><path class="abljxkb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:haskell" /></template>
