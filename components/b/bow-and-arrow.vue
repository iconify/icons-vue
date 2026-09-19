<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbj9wxbdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dbj9wxbdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:bow-and-arrow" /></template>
