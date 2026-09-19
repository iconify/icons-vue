<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vekcsdd2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="vekcsdd2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:filter-fill-12" /></template>
