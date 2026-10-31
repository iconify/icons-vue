<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cd20mybht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="cd20mybht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:dots-3x3-16-solid" /></template>
