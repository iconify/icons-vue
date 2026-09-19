<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yy_2mhbhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yy_2mhbhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:align-horizontal-distribute-end" /></template>
