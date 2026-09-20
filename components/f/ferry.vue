<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzc-a659z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gzc-a659z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:ferry" /></template>
