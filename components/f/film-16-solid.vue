<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oi-b3jbuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="oi-b3jbuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:film-16-solid" /></template>
