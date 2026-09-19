<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hetb5acfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hetb5acfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:arrow-right-from-line" /></template>
