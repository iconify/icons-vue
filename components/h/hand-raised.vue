<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ij9xh8x8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ij9xh8x8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:hand-raised" /></template>
