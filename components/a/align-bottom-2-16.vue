<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uo0pu5bsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uo0pu5bsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:align-bottom-2-16" /></template>
