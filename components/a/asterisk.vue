<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f39h84byu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f39h84byu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:asterisk" /></template>
