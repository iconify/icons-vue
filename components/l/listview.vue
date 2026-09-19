<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nq-rtkbev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="nq-rtkbev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:listview" /></template>
