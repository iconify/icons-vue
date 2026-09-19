<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvt6tyb5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="rvt6tyb5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:film" /></template>
