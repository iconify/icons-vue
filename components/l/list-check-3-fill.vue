<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2i4bqgxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d2i4bqgxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:list-check-3-fill" /></template>
