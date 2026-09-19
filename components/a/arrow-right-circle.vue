<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohqz0n9ms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ohqz0n9ms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:arrow-right-circle" /></template>
