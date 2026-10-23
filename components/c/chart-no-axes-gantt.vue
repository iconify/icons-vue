<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b35ugccxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b35ugccxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:chart-no-axes-gantt" /></template>
