<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uoc1v7b7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uoc1v7b7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:arrow-up-left2" /></template>
