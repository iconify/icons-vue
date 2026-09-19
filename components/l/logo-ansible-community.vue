<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icdmmo27p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="icdmmo27p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:logo-ansible-community" /></template>
