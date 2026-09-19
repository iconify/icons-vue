<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aa32aezsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="aa32aezsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:arrows-long-left" /></template>
