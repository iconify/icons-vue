<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/st5j5cbnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="st5j5cbnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:error" /></template>
