<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ca8qu3aws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ca8qu3aws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:align-center-fill-16" /></template>
