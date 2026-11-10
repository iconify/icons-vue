<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3ikzu8te.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="m3ikzu8te"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:cloud-x-mark-20-solid" /></template>
