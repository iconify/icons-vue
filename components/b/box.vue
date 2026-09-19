<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5nx49f4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="g5nx49f4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:box" /></template>
