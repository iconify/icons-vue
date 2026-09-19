<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7ztgisgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="s7ztgisgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:downloadalt" /></template>
