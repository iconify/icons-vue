<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wawe9kmgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wawe9kmgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:drag-vertical" /></template>
