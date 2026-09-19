<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xljt9gbgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xljt9gbgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:list-plus" /></template>
