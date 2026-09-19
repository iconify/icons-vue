<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mryp6pydz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="mryp6pydz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:id-card" /></template>
