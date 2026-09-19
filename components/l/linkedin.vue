<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yb8qd6bbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="yb8qd6bbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:linkedin" /></template>
