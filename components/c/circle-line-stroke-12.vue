<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxpt1mbov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="rxpt1mbov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:circle-line-stroke-12" /></template>
