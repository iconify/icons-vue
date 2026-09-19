<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2cthfofh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="a2cthfofh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:arrow-path" /></template>
