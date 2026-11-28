<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8j59_bxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a8j59_bxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:hospital-plus" /></template>
