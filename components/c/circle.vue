<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ad2u7zbmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ad2u7zbmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:circle" /></template>
