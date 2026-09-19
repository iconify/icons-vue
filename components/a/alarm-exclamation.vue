<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjpmnbata.css';
import '../../css/k/ku47_bc8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rjpmnbata"/><path class="ku47_bc8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:alarm-exclamation" /></template>
