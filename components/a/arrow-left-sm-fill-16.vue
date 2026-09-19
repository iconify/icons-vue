<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hyx4-db_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hyx4-db_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:arrow-left-sm-fill-16" /></template>
