<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdz-l3bia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="kdz-l3bia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:align-left-fill-12" /></template>
