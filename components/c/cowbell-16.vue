<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sb6u6tbuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="sb6u6tbuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:cowbell-16" /></template>
