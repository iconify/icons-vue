<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbhk0pjwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="cbhk0pjwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:beaker" /></template>
