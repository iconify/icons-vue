<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pd_wmlbtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="pd_wmlbtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:githubcopilot" /></template>
