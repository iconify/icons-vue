<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8o49bcjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="p8o49bcjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:form-library-mirrored" /></template>
