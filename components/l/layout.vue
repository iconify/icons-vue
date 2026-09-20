<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzegt-b6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qzegt-b6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:layout" /></template>
