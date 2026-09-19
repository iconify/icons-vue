<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7xw2l-ms.css';
import '../../css/v/vp3r9_80y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="e7xw2l-ms"/><path class="vp3r9_80y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:htmx" /></template>
