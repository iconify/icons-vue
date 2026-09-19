<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vv0pf1iqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vv0pf1iqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:123-fill-16" /></template>
