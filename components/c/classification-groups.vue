<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfuw7jbfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mfuw7jbfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:classification-groups" /></template>
