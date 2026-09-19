<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eie8mt2ml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="eie8mt2ml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:divide-square" /></template>
