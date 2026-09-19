<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-mv2ybyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="t-mv2ybyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:facebook" /></template>
