<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9-ydhbwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="h9-ydhbwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:consul" /></template>
