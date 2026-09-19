<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5ur80tmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="v5ur80tmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:book-closed-fill-12" /></template>
