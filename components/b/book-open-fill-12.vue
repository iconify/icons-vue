<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdhdgrbkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="qdhdgrbkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:book-open-fill-12" /></template>
