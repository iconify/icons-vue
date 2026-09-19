<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r16t1096v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r16t1096v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:flux" /></template>
