<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xun-ug0px.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xun-ug0px"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:folder-plus" /></template>
