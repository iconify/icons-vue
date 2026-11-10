<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/of_zlmdfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="of_zlmdfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:haxe" /></template>
