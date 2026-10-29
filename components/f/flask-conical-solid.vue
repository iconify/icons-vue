<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrr6zx6_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zrr6zx6_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:flask-conical-solid" /></template>
