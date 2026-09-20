<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmp54ibxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hmp54ibxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:harmonica-16" /></template>
