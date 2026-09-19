<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_o3b9txh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_o3b9txh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dish-filled" /></template>
