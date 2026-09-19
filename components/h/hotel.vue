<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzbf6_b4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="qzbf6_b4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:hotel" /></template>
