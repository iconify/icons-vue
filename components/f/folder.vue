<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edz6g3fgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":384};
const content = `<path class="edz6g3fgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:folder" /></template>
