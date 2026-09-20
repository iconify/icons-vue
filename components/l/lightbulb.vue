<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3hq6lb8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="z3hq6lb8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:lightbulb" /></template>
