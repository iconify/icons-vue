<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zv82l7bbi.css';
import '../../css/o/op4z4jb0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zv82l7bbi"/><path class="op4z4jb0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:chart-bar-big-rows" /></template>
