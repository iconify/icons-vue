<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l82073shy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="l82073shy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:clipboard-20-solid" /></template>
