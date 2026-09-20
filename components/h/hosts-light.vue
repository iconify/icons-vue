<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1sz4db_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v1sz4db_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:hosts-light" /></template>
