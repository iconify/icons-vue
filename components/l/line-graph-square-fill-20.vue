<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grb5_qoaa.css';
import '../../css/p/pwjqkc8pr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="grb5_qoaa"/><path class="pwjqkc8pr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:line-graph-square-fill-20" /></template>
