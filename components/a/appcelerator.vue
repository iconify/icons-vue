<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwi_mlb7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="qwi_mlb7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:appcelerator" /></template>
