<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vw4d-fjve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vw4d-fjve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:duplicate-fill-16" /></template>
