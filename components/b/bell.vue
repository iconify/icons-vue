<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7bae4kho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f7bae4kho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:bell" /></template>
