<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9aspjb5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="l9aspjb5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:arrow-up-left" /></template>
