<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udxgnlb5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="udxgnlb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:apple" /></template>
