<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omem0ccop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="omem0ccop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:dots-horizontal" /></template>
