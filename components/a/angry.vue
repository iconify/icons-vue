<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljhi_bcxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljhi_bcxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:angry" /></template>
