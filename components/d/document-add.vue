<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xppq04p1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="xppq04p1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:document-add" /></template>
