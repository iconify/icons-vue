<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7ck4bbqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="a7ck4bbqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:briefcase-with-venus" /></template>
