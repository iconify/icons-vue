<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gcv2s-lwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gcv2s-lwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:bars-3-bottom-left-16-solid" /></template>
