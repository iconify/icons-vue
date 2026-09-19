<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cirejz0cc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cirejz0cc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:bal" /></template>
