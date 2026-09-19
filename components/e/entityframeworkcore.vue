<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vifyjob0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="vifyjob0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:entityframeworkcore" /></template>
