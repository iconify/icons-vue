<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_cqrlblh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="q_cqrlblh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:cloud-arrow-down-20-solid" /></template>
