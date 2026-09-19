<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g908y3bfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="g908y3bfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:arrow-down-on-square-stack" /></template>
