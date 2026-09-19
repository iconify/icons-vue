<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3vi3_h6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="f3vi3_h6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:arrow-trending-down" /></template>
