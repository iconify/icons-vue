<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sm9d15bqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sm9d15bqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:bell-plus" /></template>
