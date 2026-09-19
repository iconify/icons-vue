<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtqpr-xro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":472};
const content = `<path class="dtqpr-xro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:cocktail" /></template>
