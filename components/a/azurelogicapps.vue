<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofz-09bxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ofz-09bxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:azurelogicapps" /></template>
