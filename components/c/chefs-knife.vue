<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7j76tezx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="e7j76tezx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:chefs-knife" /></template>
