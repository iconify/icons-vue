<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5woho7hw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="s5woho7hw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:ansys" /></template>
