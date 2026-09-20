<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agp85jbls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="agp85jbls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:cadillac" /></template>
