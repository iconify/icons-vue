<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zht8thbji.css';
import '../../css/q/qb4cy_fkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zht8thbji"/><path class="qb4cy_fkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:clone" /></template>
