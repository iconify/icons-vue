<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqp5sdsio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="sqp5sdsio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:card-club" /></template>
