<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tx5b0f8ph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":384};
const content = `<path class="tx5b0f8ph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:folder-outline" /></template>
