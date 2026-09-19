<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wd9fb2r4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wd9fb2r4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:arrow-uturn-right-down" /></template>
