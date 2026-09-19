<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gk82qcokj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gk82qcokj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:do-not-sit" /></template>
