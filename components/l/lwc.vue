<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oys82-bsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="oys82-bsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:lwc" /></template>
