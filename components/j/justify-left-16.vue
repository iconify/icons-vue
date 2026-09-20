<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwwtl8bab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zwwtl8bab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:justify-left-16" /></template>
