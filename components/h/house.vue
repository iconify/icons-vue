<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vw6r-lbms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vw6r-lbms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:house" /></template>
