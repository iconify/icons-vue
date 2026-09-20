<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4qw-tb_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d4qw-tb_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:diving-scuba-mask" /></template>
