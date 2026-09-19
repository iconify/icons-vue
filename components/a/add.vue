<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj-zwf-qp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fj-zwf-qp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:add" /></template>
