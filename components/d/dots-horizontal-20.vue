<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ug3_nnb3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ug3_nnb3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:dots-horizontal-20" /></template>
