<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x63i9lbue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x63i9lbue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:index-open" /></template>
