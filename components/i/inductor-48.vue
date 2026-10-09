<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5nl8rbtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v5nl8rbtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:inductor-48" /></template>
