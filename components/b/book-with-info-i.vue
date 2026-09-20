<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1hp8hbgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="r1hp8hbgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:book-with-info-i" /></template>
