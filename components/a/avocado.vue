<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_-0hib6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_-0hib6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:avocado" /></template>
