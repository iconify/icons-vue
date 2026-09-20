<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojtwr_bkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojtwr_bkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ela" /></template>
