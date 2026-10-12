<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bm3-8ybbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bm3-8ybbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:lock-fill-20" /></template>
