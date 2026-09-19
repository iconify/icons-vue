<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxiassbwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="nxiassbwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-trending-up-20-solid" /></template>
