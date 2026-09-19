<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evgd5di7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="evgd5di7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-down-left-square" /></template>
