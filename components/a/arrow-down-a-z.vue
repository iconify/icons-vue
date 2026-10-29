<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sm07_l1yl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sm07_l1yl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-down-a-z" /></template>
