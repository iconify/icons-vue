<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uklbqccbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uklbqccbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:exclamation-mark" /></template>
