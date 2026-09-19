<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8w016b_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="h8w016b_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:grid" /></template>
