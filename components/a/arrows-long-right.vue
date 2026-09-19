<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7pwbu_lf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h7pwbu_lf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:arrows-long-right" /></template>
