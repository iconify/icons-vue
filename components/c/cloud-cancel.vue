<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yj5q7orcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yj5q7orcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:cloud-cancel" /></template>
