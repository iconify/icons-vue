<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lp18g_5dc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lp18g_5dc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:chat-alt-2" /></template>
