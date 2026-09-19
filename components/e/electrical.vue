<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g52e4xb1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g52e4xb1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:electrical" /></template>
