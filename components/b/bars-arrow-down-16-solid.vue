<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zor06vbkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zor06vbkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:bars-arrow-down-16-solid" /></template>
