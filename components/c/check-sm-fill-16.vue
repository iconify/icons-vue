<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-n4i5b7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c-n4i5b7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:check-sm-fill-16" /></template>
