<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trjilpbgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="trjilpbgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:cool" /></template>
