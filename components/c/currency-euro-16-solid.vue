<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xz6yknbnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xz6yknbnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:currency-euro-16-solid" /></template>
