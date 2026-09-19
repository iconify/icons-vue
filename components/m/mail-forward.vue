<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itkqu9bwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1600};
const content = `<path class="itkqu9bwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:mail-forward" /></template>
