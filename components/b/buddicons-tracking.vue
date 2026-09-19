<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjdajlbqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xjdajlbqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:buddicons-tracking" /></template>
