<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6jy5bc9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":814,"height":1000};
const content = `<path class="z6jy5bc9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:apple-dark" /></template>
