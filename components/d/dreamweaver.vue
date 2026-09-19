<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nk-0nwoxu.css';
import '../../css/k/klrrfacgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="nk-0nwoxu"/><path class="klrrfacgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:dreamweaver" /></template>
