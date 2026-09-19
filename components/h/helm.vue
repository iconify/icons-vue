<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qc-n21bez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="qc-n21bez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:helm" /></template>
