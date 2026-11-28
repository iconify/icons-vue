<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpih66b8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qpih66b8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-right-square-solid" /></template>
