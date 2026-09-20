<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p99d2z6jh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="p99d2z6jh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:basic-ui-remove-2" /></template>
