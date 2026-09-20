<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5170fbol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="y5170fbol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:back" /></template>
