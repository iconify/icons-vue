<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c26tp36kj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c26tp36kj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:exclamation" /></template>
