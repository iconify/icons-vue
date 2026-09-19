<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xm0v-e0ee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xm0v-e0ee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-turn-down-left-16-solid" /></template>
