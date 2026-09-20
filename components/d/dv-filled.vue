<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_v7-qb4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_v7-qb4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:dv-filled" /></template>
