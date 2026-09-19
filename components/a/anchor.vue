<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyfzb6bca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="eyfzb6bca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:anchor" /></template>
