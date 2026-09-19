<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thtczq8qt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="thtczq8qt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:arrow-up-circle" /></template>
