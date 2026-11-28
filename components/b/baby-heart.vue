<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qp880nzii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qp880nzii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:baby-heart" /></template>
