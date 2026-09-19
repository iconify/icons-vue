<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsqr_kr0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="rsqr_kr0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:luau" /></template>
