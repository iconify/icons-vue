<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4cve9bhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="u4cve9bhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-trending-up-16-solid" /></template>
