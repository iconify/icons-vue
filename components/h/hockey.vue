<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyc_-70uy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="dyc_-70uy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:hockey" /></template>
