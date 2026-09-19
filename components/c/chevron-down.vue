<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsj5vxb2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="dsj5vxb2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:chevron-down" /></template>
