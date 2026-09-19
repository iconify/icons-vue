<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3jc4r7_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3jc4r7_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cursor-click" /></template>
