<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vz4oqrbit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="vz4oqrbit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:arrow-trending-up" /></template>
