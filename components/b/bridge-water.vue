<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dudglib1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="dudglib1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:bridge-water" /></template>
