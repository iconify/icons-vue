<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_1g1vocv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_1g1vocv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:activity-duo" /></template>
