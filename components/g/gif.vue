<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygj70ub7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ygj70ub7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:gif" /></template>
