<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktvr3tbmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ktvr3tbmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-path-20-solid" /></template>
