<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shc64lbnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="shc64lbnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:link" /></template>
