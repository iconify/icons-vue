<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohs3nursk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ohs3nursk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:cauldron" /></template>
