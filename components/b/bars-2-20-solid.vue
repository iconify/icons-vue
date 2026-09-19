<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtyv3plye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="qtyv3plye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:bars-2-20-solid" /></template>
