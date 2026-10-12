<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9kqie5ws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o9kqie5ws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:arrow-diagonal-in-20" /></template>
