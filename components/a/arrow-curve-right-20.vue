<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttz5xjg0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ttz5xjg0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:arrow-curve-right-20" /></template>
