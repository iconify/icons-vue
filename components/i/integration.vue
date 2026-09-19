<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xukg1wjzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xukg1wjzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:integration" /></template>
