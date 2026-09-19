<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw7r68gtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="iw7r68gtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:banknote-stroke-16" /></template>
