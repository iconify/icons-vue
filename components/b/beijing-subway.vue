<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cv1xizbgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cv1xizbgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:beijing-subway" /></template>
