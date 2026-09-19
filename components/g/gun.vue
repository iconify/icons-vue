<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1tu19bmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g1tu19bmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:gun" /></template>
