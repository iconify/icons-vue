<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/expt5jbwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1023};
const content = `<path class="expt5jbwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:checkbox" /></template>
