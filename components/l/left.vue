<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4gessbux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":7,"height":16};
const content = `<path class="h4gessbux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:left" /></template>
