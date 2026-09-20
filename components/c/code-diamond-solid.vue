<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxbrv1zbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oxbrv1zbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:code-diamond-solid" /></template>
