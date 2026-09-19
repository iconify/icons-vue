<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r000_c16s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r000_c16s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:edoge" /></template>
