<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxhq8sj5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="zxhq8sj5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:arrows-expand" /></template>
