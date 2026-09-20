<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8vm9wbei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="n8vm9wbei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ahrefs" /></template>
