<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfmt0acwz.css';
import '../../css/t/tc0qvy92q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qfmt0acwz"/><path class="tc0qvy92q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:building-small" /></template>
