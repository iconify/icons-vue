<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/leg09-b4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="leg09-b4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:crop" /></template>
