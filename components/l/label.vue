<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvykx2zxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="pvykx2zxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:label" /></template>
