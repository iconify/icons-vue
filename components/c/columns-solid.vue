<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxkark7nm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qxkark7nm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:columns-solid" /></template>
