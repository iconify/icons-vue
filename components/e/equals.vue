<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/th6h_28ds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":768};
const content = `<path class="th6h_28ds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:equals" /></template>
