<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1q1bljxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t1q1bljxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dock-bottom-right-alt-filled" /></template>
