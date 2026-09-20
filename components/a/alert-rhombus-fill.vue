<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/baly-1ssn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="baly-1ssn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:alert-rhombus-fill" /></template>
