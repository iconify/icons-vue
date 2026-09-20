<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9q_cmbkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a9q_cmbkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:grab" /></template>
