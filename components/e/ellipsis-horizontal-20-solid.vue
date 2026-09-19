<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ui15hlbwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ui15hlbwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:ellipsis-horizontal-20-solid" /></template>
