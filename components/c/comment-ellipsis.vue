<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_824rryb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h_824rryb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:comment-ellipsis" /></template>
