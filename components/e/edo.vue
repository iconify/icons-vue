<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nl5ob1sld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nl5ob1sld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:edo" /></template>
