<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cv4d2ta5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-6};
const content = `<path class="cv4d2ta5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:coffee-cup" /></template>
