<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xahhzk8rq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xahhzk8rq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:eyedropper" /></template>
