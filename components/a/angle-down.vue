<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcs96yn7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zcs96yn7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:angle-down" /></template>
