<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2yu1ib7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="h2yu1ib7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:alert-rhombus" /></template>
