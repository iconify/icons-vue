<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etwxr4bvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="etwxr4bvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:hard-hat-check" /></template>
