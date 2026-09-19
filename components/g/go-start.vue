<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sb-t67w8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sb-t67w8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:go-start" /></template>
