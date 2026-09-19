<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w37f9tbrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w37f9tbrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:coffee" /></template>
