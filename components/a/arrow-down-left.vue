<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sovv55ykt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sovv55ykt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:arrow-down-left" /></template>
