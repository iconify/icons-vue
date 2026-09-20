<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uoac7cc0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uoac7cc0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:bug" /></template>
