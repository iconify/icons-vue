<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qb1rmu98c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qb1rmu98c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-rupee" /></template>
