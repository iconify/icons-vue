<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jiw71x5na.css';
import '../../css/d/dvmj74bcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="jiw71x5na"/><path class="dvmj74bcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:dependabot" /></template>
