<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7krgy5kr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w7krgy5kr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:copy-off" /></template>
