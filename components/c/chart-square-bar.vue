<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plt0i6b8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="plt0i6b8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:chart-square-bar" /></template>
