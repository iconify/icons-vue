<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zoy5q4b1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="zoy5q4b1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:folder-plus" /></template>
