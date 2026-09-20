<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpwgw71rg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="lpwgw71rg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:cube" /></template>
