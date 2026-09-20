<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcy-b-u_j.css';
import '../../css/u/u-e1w8b5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xcy-b-u_j"/><path class="u-e1w8b5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:arrow-circle-up-o" /></template>
