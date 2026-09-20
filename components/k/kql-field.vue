<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdcoovbta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":10};
const content = `<path class="tdcoovbta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:kql-field" /></template>
