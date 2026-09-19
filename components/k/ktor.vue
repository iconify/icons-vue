<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xw_v8cb9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="xw_v8cb9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:ktor" /></template>
