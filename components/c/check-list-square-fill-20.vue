<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8j-v7bth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z8j-v7bth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:check-list-square-fill-20" /></template>
