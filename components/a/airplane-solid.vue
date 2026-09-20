<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rablo__dc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rablo__dc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:airplane-solid" /></template>
