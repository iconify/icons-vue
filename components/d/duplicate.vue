<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0jpl0b7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="c0jpl0b7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:duplicate" /></template>
