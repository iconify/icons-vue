<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9tob4f4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u9tob4f4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:arrows-down" /></template>
