<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uv43l2zsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uv43l2zsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:frappe" /></template>
