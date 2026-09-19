<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-fum9tds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o-fum9tds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:collection-fill" /></template>
