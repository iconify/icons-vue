<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfc8nsb1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zfc8nsb1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:infinity-duo" /></template>
