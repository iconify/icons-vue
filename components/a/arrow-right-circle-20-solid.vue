<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9u-0nb5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="l9u-0nb5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-right-circle-20-solid" /></template>
