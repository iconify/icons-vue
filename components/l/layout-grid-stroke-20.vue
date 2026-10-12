<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mr_ceabby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mr_ceabby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:layout-grid-stroke-20" /></template>
