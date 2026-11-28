<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xg1eb4bcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xg1eb4bcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:loader-duo" /></template>
