<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myd67uc3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="myd67uc3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:layout-rows" /></template>
