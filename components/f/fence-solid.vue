<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3i4igydq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3i4igydq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:fence-solid" /></template>
