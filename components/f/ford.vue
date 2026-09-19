<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yg8yavbyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yg8yavbyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ford" /></template>
