<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srcpcbb9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":304,"height":448};
const content = `<path class="srcpcbb9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:arrow-up" /></template>
