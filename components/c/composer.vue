<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fk617r-oj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fk617r-oj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:composer" /></template>
