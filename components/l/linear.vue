<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-1york6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="u-1york6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:linear" /></template>
