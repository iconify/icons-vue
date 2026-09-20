<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y086wwr5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="y086wwr5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:chevron-double-lg-left" /></template>
