<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jy9xnq4db.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jy9xnq4db"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:dependency" /></template>
