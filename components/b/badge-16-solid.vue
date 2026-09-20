<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obo01usqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="obo01usqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:badge-16-solid" /></template>
