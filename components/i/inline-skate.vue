<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azezztbis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="azezztbis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:inline-skate" /></template>
