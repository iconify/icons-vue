<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebax7cb2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ebax7cb2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:bars-2" /></template>
