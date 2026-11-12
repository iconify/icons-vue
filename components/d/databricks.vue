<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tc3v_0bsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="tc3v_0bsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:databricks" /></template>
