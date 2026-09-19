<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umx86bbwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="umx86bbwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:elasticsearch" /></template>
