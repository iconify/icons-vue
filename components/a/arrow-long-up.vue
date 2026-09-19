<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a92qnq0-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="a92qnq0-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:arrow-long-up" /></template>
