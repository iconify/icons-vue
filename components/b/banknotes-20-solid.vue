<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0x4f1bmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="n0x4f1bmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:banknotes-20-solid" /></template>
