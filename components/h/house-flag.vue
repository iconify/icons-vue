<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/af4-9ib1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="af4-9ib1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:house-flag" /></template>
