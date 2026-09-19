<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shan8t4to.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="shan8t4to"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:dazn" /></template>
