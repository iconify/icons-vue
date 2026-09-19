<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uctknnc3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="uctknnc3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:7" /></template>
