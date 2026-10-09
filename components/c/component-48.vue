<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opxm96fzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="opxm96fzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:component-48" /></template>
