<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzdfx8aph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="dzdfx8aph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:asc" /></template>
