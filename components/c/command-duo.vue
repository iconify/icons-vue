<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gt-8uk4il.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gt-8uk4il"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:command-duo" /></template>
