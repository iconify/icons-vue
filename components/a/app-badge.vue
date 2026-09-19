<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzc-6c3do.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="gzc-6c3do"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:app-badge" /></template>
