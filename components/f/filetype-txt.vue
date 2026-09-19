<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywruj_bdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ywruj_bdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:filetype-txt" /></template>
