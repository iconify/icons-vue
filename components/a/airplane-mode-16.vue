<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b630ko33l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b630ko33l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:airplane-mode-16" /></template>
