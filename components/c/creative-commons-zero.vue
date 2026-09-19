<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4b4ymh5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="o4b4ymh5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:creative-commons-zero" /></template>
