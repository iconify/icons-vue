<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4zn6vxvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r4zn6vxvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:doctor" /></template>
