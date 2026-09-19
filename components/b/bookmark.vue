<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axep7gbhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="axep7gbhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:bookmark" /></template>
