<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pybr84bnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pybr84bnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:command-gloss" /></template>
