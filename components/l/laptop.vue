<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-1u6ubtf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="v-1u6ubtf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:laptop" /></template>
