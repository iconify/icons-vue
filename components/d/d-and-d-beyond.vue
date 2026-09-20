<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azxiujbpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="azxiujbpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:d-and-d-beyond" /></template>
