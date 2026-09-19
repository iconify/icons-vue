<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zv82l7bbi.css';
import '../../css/a/arue7cbqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b zv82l7bbi"/><path class="arue7cbqf b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:chart-network" /></template>
