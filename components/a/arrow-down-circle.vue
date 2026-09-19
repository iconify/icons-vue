<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8cbc2bmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="q8cbc2bmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:arrow-down-circle" /></template>
