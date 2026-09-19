<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1iq1p1eb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="a1iq1p1eb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:dynatrace" /></template>
