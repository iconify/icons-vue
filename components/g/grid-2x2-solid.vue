<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbnwhwoyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbnwhwoyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:grid-2x2-solid" /></template>
