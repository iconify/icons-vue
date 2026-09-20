<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztgqxrd3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ztgqxrd3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:lines" /></template>
