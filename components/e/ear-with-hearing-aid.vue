<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dk6a6dbmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dk6a6dbmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:ear-with-hearing-aid" /></template>
