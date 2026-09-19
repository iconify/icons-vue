<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydqxd-b9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ydqxd-b9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:line-l" /></template>
